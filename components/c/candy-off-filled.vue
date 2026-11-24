<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj2q-yklp.css';
import '../../css/v/v7flhwbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dj2q-yklp"/><path class="v7flhwbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:candy-off-filled" /></template>
