<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh3o1ob7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3o1ob7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cigarette-filled" /></template>
