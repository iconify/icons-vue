<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax_k84bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ax_k84bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:envelope" /></template>
