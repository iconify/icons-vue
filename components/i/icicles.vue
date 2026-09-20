<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za2b7ublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="za2b7ublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:icicles" /></template>
