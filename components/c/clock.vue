<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-c9soo6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-c9soo6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock" /></template>
