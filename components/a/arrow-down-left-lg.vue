<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzd7lybys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzd7lybys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-down-left-lg" /></template>
