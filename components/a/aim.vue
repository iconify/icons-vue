<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow134470u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":488};
const content = `<path class="ow134470u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:aim" /></template>
