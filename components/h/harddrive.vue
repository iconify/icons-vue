<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdom31c5r.css';
import '../../css/w/wp43u2bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fdom31c5r"/><path class="wp43u2bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:harddrive" /></template>
