<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uum2aj53r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uum2aj53r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:facebook-gaming" /></template>
