<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozk_7lbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozk_7lbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:blockquote-fill" /></template>
