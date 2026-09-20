<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv_eflodi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iv_eflodi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-circle-bold" /></template>
