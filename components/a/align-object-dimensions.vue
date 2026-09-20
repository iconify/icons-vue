<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcuhrcb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcuhrcb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-object-dimensions" /></template>
