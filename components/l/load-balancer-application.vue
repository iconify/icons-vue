<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq2n3-29f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eq2n3-29f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-application" /></template>
