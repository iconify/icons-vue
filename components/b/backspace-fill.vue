<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae9euyb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae9euyb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:backspace-fill" /></template>
