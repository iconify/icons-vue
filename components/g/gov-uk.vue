<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzi20bcby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xzi20bcby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gov-uk" /></template>
