<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-wun7bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-wun7bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:database" /></template>
