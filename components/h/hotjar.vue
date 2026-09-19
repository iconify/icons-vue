<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndyzunb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndyzunb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hotjar" /></template>
