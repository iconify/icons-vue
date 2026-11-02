<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7ny22t_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7ny22t_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-right" /></template>
