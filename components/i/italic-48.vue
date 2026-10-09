<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwlek8bjm.css';
import '../../css/o/onp3hbbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jwlek8bjm"/><path class="onp3hbbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:italic-48" /></template>
