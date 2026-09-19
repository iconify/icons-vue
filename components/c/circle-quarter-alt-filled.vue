<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbhjbxbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbhjbxbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-quarter-alt-filled" /></template>
