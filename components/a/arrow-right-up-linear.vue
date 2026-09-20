<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg_3v5bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg_3v5bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-linear" /></template>
