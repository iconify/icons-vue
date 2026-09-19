<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evbui5r_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="evbui5r_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:delicious" /></template>
