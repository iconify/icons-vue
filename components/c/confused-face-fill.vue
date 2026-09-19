<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-28ubbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-28ubbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:confused-face-fill" /></template>
