<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_89xsb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v_89xsb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fastapi" /></template>
