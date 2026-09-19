<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wclb063ro.css';
import '../../css/l/lzqod34yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wclb063ro"/><path class="lzqod34yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hard-drive" /></template>
