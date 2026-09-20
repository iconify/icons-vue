<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lta4h9b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lta4h9b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:addthis" /></template>
