<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewug2tztv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewug2tztv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-plus" /></template>
