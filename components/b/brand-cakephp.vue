<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4a9otb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4a9otb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-cakephp" /></template>
