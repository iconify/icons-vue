<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbz8f1bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbz8f1bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beer" /></template>
