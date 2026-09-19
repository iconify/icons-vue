<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klcn6tchx.css';
import '../../css/n/ng1infulf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klcn6tchx"/><path class="ng1infulf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pricetag-outline" /></template>
