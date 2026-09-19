<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6ec_n6vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6ec_n6vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-forward-sharp" /></template>
