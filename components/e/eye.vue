<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtmr7iqcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="xtmr7iqcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:eye" /></template>
