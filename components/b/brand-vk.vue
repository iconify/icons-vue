<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbo42nb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbo42nb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-vk" /></template>
