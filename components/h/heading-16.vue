<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hogsm-1xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hogsm-1xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:heading-16" /></template>
