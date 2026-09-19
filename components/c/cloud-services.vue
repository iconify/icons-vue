<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqnfqd2jd.css';
import '../../css/r/rpr4dyb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nqnfqd2jd"/><path class="rpr4dyb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-services" /></template>
