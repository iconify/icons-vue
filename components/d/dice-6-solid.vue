<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipt536azn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipt536azn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dice-6-solid" /></template>
