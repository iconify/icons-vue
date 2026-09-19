<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3t9q1bdx.css';
import '../../css/b/bgdvneanc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3t9q1bdx"/><path class="bgdvneanc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:credit-card-front" /></template>
