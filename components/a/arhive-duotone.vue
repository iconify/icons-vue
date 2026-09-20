<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9_jpg2jv.css';
import '../../css/c/c287m3bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9_jpg2jv"/><path clip-rule="evenodd" class="c287m3bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arhive-duotone" /></template>
