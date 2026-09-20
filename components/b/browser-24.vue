<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsriy4b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsriy4b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:browser-24" /></template>
