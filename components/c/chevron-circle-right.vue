<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rasaarb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="rasaarb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-circle-right" /></template>
