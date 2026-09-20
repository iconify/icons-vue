<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqtki0bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fqtki0bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:gift" /></template>
