<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox2vwfbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ox2vwfbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-hearts" /></template>
