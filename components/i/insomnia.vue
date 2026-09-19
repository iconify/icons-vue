<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_ur5bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xr_ur5bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:insomnia" /></template>
