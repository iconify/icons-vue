<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qur8xabfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qur8xabfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:delta" /></template>
