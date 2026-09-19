<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm5sbg_7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm5sbg_7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:duck-filled" /></template>
