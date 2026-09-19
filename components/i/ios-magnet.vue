<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owmnm1tqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="owmnm1tqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-magnet" /></template>
