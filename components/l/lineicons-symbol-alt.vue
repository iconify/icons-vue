<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr4-27x8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kr4-27x8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:lineicons-symbol-alt" /></template>
