<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6v_o1bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6v_o1bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-check-bold" /></template>
