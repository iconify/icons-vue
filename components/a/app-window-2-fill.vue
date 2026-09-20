<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_aw2bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru_aw2bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-2-fill" /></template>
