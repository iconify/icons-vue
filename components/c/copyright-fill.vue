<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lumh9kbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lumh9kbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:copyright-fill" /></template>
