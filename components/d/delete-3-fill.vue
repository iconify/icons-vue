<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btuo6vbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btuo6vbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-3-fill" /></template>
