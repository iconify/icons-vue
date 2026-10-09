<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpmgkheit.css';
import '../../css/r/rw5av3bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpmgkheit"/><path class="rw5av3bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apartment-48-bold" /></template>
