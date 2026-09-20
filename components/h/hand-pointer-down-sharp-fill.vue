<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_1jzeb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_1jzeb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-down-sharp-fill" /></template>
