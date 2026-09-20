<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrs2_fwzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrs2_fwzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:attachment-upload" /></template>
