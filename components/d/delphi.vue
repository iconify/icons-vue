<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igvua1b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="igvua1b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:delphi" /></template>
