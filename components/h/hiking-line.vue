<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh-z6dbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh-z6dbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hiking-line" /></template>
