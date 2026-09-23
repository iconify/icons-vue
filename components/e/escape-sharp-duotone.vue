<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c14fq_mes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c14fq_mes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escape-sharp-duotone" /></template>
