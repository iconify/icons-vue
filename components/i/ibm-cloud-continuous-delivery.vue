<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw038zbvw.css';
import '../../css/n/nr8b-db0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tw038zbvw"/><path class="nr8b-db0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-continuous-delivery" /></template>
