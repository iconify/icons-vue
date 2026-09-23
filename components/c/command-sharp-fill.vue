<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-up1856y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-up1856y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:command-sharp-fill" /></template>
