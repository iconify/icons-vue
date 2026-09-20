<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7-yaib4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7-yaib4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ignis" /></template>
