<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc54kia8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc54kia8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firezone-light" /></template>
