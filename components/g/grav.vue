<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuxgncb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1824,"height":1792};
const content = `<path class="wuxgncb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:grav" /></template>
