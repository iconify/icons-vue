<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtnme21ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vtnme21ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:heart" /></template>
