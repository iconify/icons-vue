<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ccfk07g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ccfk07g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-right" /></template>
