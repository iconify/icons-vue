<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8nhe2byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8nhe2byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-key" /></template>
