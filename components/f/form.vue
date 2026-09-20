<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhw9w1klx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhw9w1klx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:form" /></template>
