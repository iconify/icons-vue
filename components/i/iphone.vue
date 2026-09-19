<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktvza_ycb.css';
import '../../css/a/ajbc88bet.css';
import '../../css/u/u9db6-ydy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktvza_ycb"/><path class="ajbc88bet"/><circle class="u9db6-ydy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:iphone" /></template>
