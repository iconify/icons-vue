<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piui6-jib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piui6-jib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ghost-filled" /></template>
