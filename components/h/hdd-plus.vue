<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjd6egtjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjd6egtjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hdd-plus" /></template>
