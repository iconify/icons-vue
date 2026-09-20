<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh55owlqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nh55owlqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:galactic-senate" /></template>
