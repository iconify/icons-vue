<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5k6uosue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5k6uosue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-twice-square-bold" /></template>
