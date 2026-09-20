<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4czdbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl4czdbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flowinquiry-light" /></template>
