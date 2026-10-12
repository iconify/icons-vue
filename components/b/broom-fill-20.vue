<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr2ks5bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vr2ks5bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:broom-fill-20" /></template>
