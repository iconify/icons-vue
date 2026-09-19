<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4rpuubib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4rpuubib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fullscreen-filled" /></template>
