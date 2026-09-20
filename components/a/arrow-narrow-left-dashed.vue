<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw6wnr8nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw6wnr8nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-left-dashed" /></template>
