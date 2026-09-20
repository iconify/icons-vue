<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyekt5j2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qyekt5j2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:check-fill" /></template>
