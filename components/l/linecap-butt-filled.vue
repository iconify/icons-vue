<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myx9f4b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myx9f4b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linecap-butt-filled" /></template>
