<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyioyxu9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyioyxu9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:adobe-alt" /></template>
