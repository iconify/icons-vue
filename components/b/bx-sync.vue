<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvt5rskls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvt5rskls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sync" /></template>
