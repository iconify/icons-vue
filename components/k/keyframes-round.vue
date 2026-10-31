<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beh9hpboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beh9hpboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyframes-round" /></template>
