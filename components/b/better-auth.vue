<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwr-6db9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwr-6db9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:better-auth" /></template>
