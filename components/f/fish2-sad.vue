<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78ylohav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s78ylohav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish2-sad" /></template>
