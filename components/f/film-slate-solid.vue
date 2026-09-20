<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ispp-yb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ispp-yb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:film-slate-solid" /></template>
