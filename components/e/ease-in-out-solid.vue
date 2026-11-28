<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bckagbb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bckagbb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ease-in-out-solid" /></template>
