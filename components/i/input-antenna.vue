<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa2vsbctw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":464};
const content = `<path class="oa2vsbctw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:input-antenna" /></template>
