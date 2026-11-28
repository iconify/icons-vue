<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8xmyqbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8xmyqbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:caravan" /></template>
