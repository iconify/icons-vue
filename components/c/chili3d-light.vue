<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0aye_mhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0aye_mhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chili3d-light" /></template>
