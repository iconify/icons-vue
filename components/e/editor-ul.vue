<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kad5kn6pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kad5kn6pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-ul" /></template>
