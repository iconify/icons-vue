<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8guv1byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8guv1byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-check-outline" /></template>
