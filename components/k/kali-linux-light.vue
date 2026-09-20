<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzj-g5bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzj-g5bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kali-linux-light" /></template>
