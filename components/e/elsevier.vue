<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad55pdbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad55pdbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:elsevier" /></template>
