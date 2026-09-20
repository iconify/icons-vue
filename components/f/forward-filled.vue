<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrnuwrb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrnuwrb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:forward-filled" /></template>
