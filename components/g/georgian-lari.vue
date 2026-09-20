<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrqv0rx5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrqv0rx5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:georgian-lari" /></template>
