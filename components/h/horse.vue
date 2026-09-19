<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj32j_biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mj32j_biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:horse" /></template>
