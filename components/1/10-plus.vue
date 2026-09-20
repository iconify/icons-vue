<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvyr0b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txvyr0b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:10-plus" /></template>
