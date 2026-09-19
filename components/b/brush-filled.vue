<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8l-jmhst.css';
import '../../css/v/vqw6mobct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8l-jmhst"/><path class="vqw6mobct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brush-filled" /></template>
