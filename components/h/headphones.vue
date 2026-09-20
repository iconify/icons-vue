<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_p9tyzab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_p9tyzab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:headphones" /></template>
