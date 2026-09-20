<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl2z-j7sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl2z-j7sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dress-fill" /></template>
