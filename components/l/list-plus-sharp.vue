<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prwr0bcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prwr0bcqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-plus-sharp" /></template>
