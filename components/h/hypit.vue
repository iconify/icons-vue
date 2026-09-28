<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjx9skd3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjx9skd3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hypit" /></template>
