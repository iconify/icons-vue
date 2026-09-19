<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejh5nmbuc.css';
import '../../css/d/d7j4pp_vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ejh5nmbuc"/><path class="d7j4pp_vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-log-out" /></template>
