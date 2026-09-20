<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-r-f4b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-r-f4b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:credit-card-disable" /></template>
