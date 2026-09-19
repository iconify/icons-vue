<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg68m81-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":27};
const content = `<path class="qg68m81-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:check" /></template>
