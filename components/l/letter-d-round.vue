<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpy49rhyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpy49rhyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-d-round" /></template>
