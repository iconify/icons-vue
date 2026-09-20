<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs6lblcao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs6lblcao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apple-podcasts" /></template>
