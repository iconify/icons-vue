<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp94h521r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp94h521r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-ai" /></template>
