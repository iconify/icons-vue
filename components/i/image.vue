<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7o_u2bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":439,"height":512};
const content = `<path class="k7o_u2bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:image" /></template>
