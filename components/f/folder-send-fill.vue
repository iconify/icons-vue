<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0841vbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0841vbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-send-fill" /></template>
