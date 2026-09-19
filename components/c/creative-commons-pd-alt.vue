<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzafr3b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rzafr3b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:creative-commons-pd-alt" /></template>
