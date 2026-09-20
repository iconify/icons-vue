<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncxz46buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncxz46buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-right-top-filled" /></template>
