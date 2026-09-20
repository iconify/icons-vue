<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h59o814uu.css';
import '../../css/l/l9_rs7bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h59o814uu"/><path class="l9_rs7bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:library" /></template>
