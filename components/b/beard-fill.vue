<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fme21bcwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fme21bcwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beard-fill" /></template>
