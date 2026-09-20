<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkuelewlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkuelewlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m" /></template>
