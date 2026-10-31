<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxta4n_om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gxta4n_om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-in-box-gabled-shelter" /></template>
