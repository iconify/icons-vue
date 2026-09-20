<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqo1tlkji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqo1tlkji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-diagonal-2" /></template>
