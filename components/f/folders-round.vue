<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krh1u2c3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krh1u2c3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-round" /></template>
