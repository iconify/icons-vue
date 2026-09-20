<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-a9q7i-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n-a9q7i-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:health-services" /></template>
