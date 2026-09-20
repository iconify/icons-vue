<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzny-seit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzny-seit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-circle-left" /></template>
