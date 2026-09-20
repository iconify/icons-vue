<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojig1mf8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojig1mf8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-circle-filled" /></template>
