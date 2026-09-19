<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb23s9btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb23s9btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:keypad-outline" /></template>
