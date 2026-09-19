<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0z-itbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0z-itbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:intellect-filled" /></template>
