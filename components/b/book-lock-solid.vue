<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjcpelbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjcpelbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-lock-solid" /></template>
