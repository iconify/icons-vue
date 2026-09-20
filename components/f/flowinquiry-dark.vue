<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk5v1wbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bk5v1wbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flowinquiry-dark" /></template>
