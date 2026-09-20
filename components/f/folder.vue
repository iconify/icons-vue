<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stlte0cow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stlte0cow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:folder" /></template>
