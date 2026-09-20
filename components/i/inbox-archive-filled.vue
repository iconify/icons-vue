<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sodr2bcij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sodr2bcij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox-archive-filled" /></template>
