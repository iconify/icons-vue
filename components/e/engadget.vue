<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9fu4zqhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9fu4zqhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:engadget" /></template>
