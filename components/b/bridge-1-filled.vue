<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzgezr25l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzgezr25l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge-1-filled" /></template>
