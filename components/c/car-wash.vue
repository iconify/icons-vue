<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a12sn_bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="a12sn_bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:car-wash" /></template>
