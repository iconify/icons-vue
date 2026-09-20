<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp98f5wdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp98f5wdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-jmeter" /></template>
