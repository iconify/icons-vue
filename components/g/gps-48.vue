<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndoo8eizj.css';
import '../../css/f/fsi0i5btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ndoo8eizj"/><path class="fsi0i5btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gps-48" /></template>
