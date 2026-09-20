<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2u_3tbje.css';
import '../../css/z/znxwd8tvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s2u_3tbje"/><path class="znxwd8tvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:imaging-root-category" /></template>
