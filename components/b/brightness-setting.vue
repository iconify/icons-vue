<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogxsybcnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ogxsybcnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-setting" /></template>
