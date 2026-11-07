<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/samvw5boj.css';
import '../../css/e/epl0f9bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="samvw5boj"/><path clip-rule="evenodd" class="epl0f9bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-bold" /></template>
