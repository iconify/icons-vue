<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s04f8kb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s04f8kb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:desk-lamp" /></template>
