<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex4c8gwtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex4c8gwtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:decrypted-plus-outline" /></template>
