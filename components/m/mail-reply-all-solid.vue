<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1d1zhbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x1d1zhbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:mail-reply-all-solid" /></template>
