<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_jzx6eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_jzx6eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:illustration" /></template>
