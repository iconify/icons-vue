<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1lzyb4w.css';
import '../../css/l/l3fjs4bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yl1lzyb4w"/><path class="l3fjs4bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autobrr" /></template>
