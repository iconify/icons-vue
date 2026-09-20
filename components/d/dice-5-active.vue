<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kod3i7btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kod3i7btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-5-active" /></template>
