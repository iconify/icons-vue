<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3upbbr5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v3upbbr5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:incorrect-password" /></template>
