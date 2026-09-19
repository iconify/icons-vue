<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6rq6xrib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n6rq6xrib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:firewall-classic" /></template>
