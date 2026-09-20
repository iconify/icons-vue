<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz4blbbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz4blbbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm" /></template>
