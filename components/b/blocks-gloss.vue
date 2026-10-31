<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_xb-aqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_xb-aqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:blocks-gloss" /></template>
