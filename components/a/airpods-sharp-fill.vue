<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpe5qmjmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpe5qmjmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods-sharp-fill" /></template>
