<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfhqb8bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhqb8bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crane-off" /></template>
