<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehs67ebsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ehs67ebsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:envira" /></template>
