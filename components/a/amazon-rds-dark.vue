<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_7eu7xzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_7eu7xzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-rds-dark" /></template>
