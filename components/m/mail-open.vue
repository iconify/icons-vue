<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az9_e8bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az9_e8bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-open" /></template>
