<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weytb4irw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="weytb4irw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:amazon-aws" /></template>
