<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsyg-3lal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsyg-3lal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess" /></template>
