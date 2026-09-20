<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1rqyxbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1rqyxbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:magnifying-glass-solid" /></template>
