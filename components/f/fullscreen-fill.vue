<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2-qd9uti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2-qd9uti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-fill" /></template>
