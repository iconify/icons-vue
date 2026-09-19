<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to6b26udf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to6b26udf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beaker" /></template>
