<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abj4bbbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abj4bbbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-pen-solid" /></template>
