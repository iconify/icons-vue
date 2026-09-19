<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2n6oj1vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="e2n6oj1vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:android" /></template>
