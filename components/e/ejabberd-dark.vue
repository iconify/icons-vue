<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eng12sjsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eng12sjsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ejabberd-dark" /></template>
