<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lksl6vb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lksl6vb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-hide-fill-12" /></template>
