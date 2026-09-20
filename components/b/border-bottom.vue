<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eel8q2mzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eel8q2mzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-bottom" /></template>
