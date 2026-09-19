<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6cff_bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n6cff_bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:apacheignite" /></template>
