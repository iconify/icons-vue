<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dztqf8b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dztqf8b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:doxygen" /></template>
