<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltow3qbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":413,"height":413,"left":-78.5};
const content = `<path class="ltow3qbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-kafka-dark" /></template>
