<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcn4mte4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hcn4mte4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-framework-dark" /></template>
