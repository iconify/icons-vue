<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd63qqbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd63qqbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:face-wink" /></template>
