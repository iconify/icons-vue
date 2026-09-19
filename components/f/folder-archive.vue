<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txmg3z5ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txmg3z5ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-archive" /></template>
