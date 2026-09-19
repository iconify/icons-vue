<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shflob6rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="shflob6rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:handshake" /></template>
