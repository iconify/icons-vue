<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_6k2w7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xu_6k2w7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:checkbox-unchecked-outlined" /></template>
