<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdzr79dwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdzr79dwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-zip-x" /></template>
