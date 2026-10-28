<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-iz7cb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-iz7cb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-narrow-wide" /></template>
