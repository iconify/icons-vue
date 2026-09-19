<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhc-nwb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhc-nwb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:galaxy" /></template>
