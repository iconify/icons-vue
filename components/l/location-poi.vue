<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stgrhqeqj.css';
import '../../css/k/k1_3dpb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="stgrhqeqj"/><path class="k1_3dpb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:location-poi" /></template>
