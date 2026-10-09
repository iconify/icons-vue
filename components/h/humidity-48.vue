<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khymdnb6j.css';
import '../../css/z/zjys3ecwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khymdnb6j"/><path class="zjys3ecwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:humidity-48" /></template>
