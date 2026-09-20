<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp1j6ubpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gp1j6ubpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed-16-solid" /></template>
