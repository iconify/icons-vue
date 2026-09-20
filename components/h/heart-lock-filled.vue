<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atvzj9bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atvzj9bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-lock-filled" /></template>
