<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfwz52s2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vfwz52s2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:gift" /></template>
