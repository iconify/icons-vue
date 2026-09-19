<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4djnsbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="y4djnsbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-medium" /></template>
