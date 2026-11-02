<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om8zdxkav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om8zdxkav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-close-fill" /></template>
