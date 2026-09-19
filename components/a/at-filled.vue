<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hifub2buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hifub2buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:at-filled" /></template>
