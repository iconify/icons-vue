<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zllir3b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zllir3b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-street-view" /></template>
