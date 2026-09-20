<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veez9zr5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="veez9zr5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:chevron-up-down" /></template>
