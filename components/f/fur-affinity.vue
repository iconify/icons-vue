<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cks-37igm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cks-37igm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fur-affinity" /></template>
