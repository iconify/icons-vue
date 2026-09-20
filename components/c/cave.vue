<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwu55hr8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nwu55hr8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cave" /></template>
