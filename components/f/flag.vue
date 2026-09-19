<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp2n7ka7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp2n7ka7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:flag" /></template>
