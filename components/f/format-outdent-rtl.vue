<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_l3vcc7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="a_l3vcc7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-outdent-rtl" /></template>
