<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kps71gbrs.css';
import '../../css/z/zy_kdc0ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kps71gbrs"/><path class="zy_kdc0ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cheese-20" /></template>
