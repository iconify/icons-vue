<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whi2z9b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="whi2z9b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:find-filled" /></template>
