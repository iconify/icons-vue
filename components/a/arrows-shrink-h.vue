<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szrkq1uqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szrkq1uqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-shrink-h" /></template>
