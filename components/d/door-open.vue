<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws7kkc8ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ws7kkc8ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:door-open" /></template>
