<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj3ip275j.css';
import '../../css/k/kumpysh-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dj3ip275j"/><path class="kumpysh-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-rod-48-bold" /></template>
