<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb025pbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kb025pbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:csswizardry" /></template>
