<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzp-t0tmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bzp-t0tmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:kql-function" /></template>
