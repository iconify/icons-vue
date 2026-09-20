<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5gtv3biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5gtv3biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-center-fill" /></template>
