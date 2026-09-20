<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec1jb1alf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1jb1alf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-2-fill" /></template>
