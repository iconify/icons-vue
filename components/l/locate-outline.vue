<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f43p7lhjp.css';
import '../../css/l/lbpp58r_m.css';
import '../../css/d/dc686_elh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f43p7lhjp"/><path class="lbpp58r_m"/><path class="dc686_elh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:locate-outline" /></template>
