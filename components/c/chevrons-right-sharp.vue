<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5yjy8bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5yjy8bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-right-sharp" /></template>
