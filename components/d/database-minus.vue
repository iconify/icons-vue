<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycoy9kbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycoy9kbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-minus" /></template>
