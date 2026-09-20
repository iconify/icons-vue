<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olfxzdbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olfxzdbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-right-down-circle-filled" /></template>
