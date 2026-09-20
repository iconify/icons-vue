<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc0x3cccn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0x3cccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:behance" /></template>
