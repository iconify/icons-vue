<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-v4z3bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-v4z3bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-2-fill" /></template>
