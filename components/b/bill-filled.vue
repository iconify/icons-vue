<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vagd1bbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vagd1bbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bill-filled" /></template>
