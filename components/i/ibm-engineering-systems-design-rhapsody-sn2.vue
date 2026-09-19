<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b84h5jsba.css';
import '../../css/l/l9-hh0blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b84h5jsba"/><path class="l9-hh0blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-systems-design-rhapsody-sn2" /></template>
