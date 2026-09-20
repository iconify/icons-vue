<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5tympzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5tympzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-2-line" /></template>
