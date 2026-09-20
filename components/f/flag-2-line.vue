<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ple43knzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ple43knzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flag-2-line" /></template>
