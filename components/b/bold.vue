<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhc4o5kia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yhc4o5kia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bold" /></template>
