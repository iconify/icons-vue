<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilalk2b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilalk2b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bars" /></template>
