<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-eynfuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-eynfuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-love-fill" /></template>
