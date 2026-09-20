<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il9_oqnbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il9_oqnbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:clipboard-check" /></template>
