<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wph-eob-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wph-eob-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:float-center-outline" /></template>
