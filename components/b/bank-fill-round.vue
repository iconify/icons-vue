<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm_0jcbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm_0jcbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bank-fill-round" /></template>
