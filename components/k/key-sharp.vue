<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdkpdlb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdkpdlb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:key-sharp" /></template>
