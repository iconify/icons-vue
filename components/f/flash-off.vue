<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_d672fqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_d672fqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flash-off" /></template>
