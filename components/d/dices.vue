<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg9j5abir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg9j5abir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dices" /></template>
