<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j60a46bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j60a46bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pound-sterling-sharp-fill" /></template>
