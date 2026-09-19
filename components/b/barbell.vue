<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzaj_mpyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzaj_mpyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:barbell" /></template>
