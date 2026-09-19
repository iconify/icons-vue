<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht47o7b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht47o7b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-extension" /></template>
