<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sht37ysff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sht37ysff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-fill" /></template>
