<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii2hbuh9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2hbuh9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-a-z" /></template>
