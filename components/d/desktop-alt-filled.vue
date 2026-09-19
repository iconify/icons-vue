<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv8dltjym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv8dltjym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desktop-alt-filled" /></template>
