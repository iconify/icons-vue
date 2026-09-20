<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw4gdnb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw4gdnb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:keyboard-asterisk-1" /></template>
