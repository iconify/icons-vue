<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zyk_juu.css';
import '../../css/r/rh_8cbdbx.css';
import '../../css/w/wcr2m1pdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e8zyk_juu"/><path class="rh_8cbdbx"/><path class="wcr2m1pdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammeter-20" /></template>
