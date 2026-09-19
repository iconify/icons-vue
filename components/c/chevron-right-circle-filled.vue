<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv7nlwsiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv7nlwsiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-right-circle-filled" /></template>
