<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8defg09k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="x8defg09k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-circle-up-f" /></template>
