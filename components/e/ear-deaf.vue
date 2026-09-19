<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md5cdnbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md5cdnbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ear-deaf" /></template>
