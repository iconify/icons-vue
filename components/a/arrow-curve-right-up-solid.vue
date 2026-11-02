<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1t3o4bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1t3o4bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-up-solid" /></template>
