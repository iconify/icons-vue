<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7a3m7bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7a3m7bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fedex" /></template>
