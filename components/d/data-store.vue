<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v24ihwb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="v24ihwb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:data-store" /></template>
