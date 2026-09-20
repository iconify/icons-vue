<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_lmzkbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z_lmzkbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:5g" /></template>
