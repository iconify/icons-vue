<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9caeac_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n9caeac_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:balloon" /></template>
