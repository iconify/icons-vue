<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu3wmc3lc.css';
import '../../css/k/k6ez9jbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu3wmc3lc"/><path class="k6ez9jbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-notifications" /></template>
