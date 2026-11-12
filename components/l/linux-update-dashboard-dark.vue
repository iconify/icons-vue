<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrrtibxz.css';
import '../../css/i/i5rwfcc2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbrrtibxz"/><path class="i5rwfcc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-update-dashboard-dark" /></template>
