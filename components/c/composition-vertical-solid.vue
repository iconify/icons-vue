<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezuox2bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ezuox2bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:composition-vertical-solid" /></template>
