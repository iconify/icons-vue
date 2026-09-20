<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of6e34b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of6e34b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-contract" /></template>
