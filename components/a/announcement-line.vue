<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro-1ks86k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-1ks86k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:announcement-line" /></template>
