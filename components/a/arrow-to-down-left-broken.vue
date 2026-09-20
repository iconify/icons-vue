<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knoj3nbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knoj3nbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-left-broken" /></template>
