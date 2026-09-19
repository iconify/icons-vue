<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrb82ox7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrb82ox7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-right" /></template>
