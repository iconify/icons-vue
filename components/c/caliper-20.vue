<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myx735bdk.css';
import '../../css/g/gfw7ev9fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="myx735bdk"/><path class="gfw7ev9fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caliper-20" /></template>
