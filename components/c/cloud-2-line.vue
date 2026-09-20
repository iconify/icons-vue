<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnzy-i2jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnzy-i2jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-2-line" /></template>
