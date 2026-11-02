<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xub61jorw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xub61jorw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-fill" /></template>
