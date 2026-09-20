<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nepsg6bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nepsg6bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-2-fill" /></template>
