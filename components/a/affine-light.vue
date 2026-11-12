<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvxxdu3wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvxxdu3wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:affine-light" /></template>
