<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku4lflboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku4lflboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:0-plus" /></template>
