<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh7z4ubgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nh7z4ubgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chip-bag" /></template>
