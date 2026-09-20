<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbgurdbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbgurdbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:corsair" /></template>
