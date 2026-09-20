<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya2xpubcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya2xpubcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:copyright-filled" /></template>
