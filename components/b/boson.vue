<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa8jhvbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xa8jhvbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:boson" /></template>
