<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fshn_2bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fshn_2bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-circle" /></template>
