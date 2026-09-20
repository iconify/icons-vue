<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd835_n3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd835_n3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-down-fill" /></template>
