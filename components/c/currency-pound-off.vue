<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry6fhv99o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry6fhv99o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-pound-off" /></template>
