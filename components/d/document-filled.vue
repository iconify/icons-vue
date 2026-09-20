<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nilwtjblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nilwtjblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-filled" /></template>
