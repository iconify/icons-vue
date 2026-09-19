<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpwro45hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="xpwro45hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:italic" /></template>
