<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm6bidcwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm6bidcwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drum-fill" /></template>
