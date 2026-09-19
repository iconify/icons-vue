<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8beb-zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ml8beb-zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:featheralt" /></template>
