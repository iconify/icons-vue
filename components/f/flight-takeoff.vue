<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajsledcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":384};
const content = `<path class="ajsledcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flight-takeoff" /></template>
