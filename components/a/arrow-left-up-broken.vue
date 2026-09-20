<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb-87k45x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb-87k45x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-up-broken" /></template>
