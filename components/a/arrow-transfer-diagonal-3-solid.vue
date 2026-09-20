<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj3fw5t9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gj3fw5t9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-transfer-diagonal-3-solid" /></template>
