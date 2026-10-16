<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gysr-mb2g.css';
import '../../css/c/cnwa92bez.css';
import '../../css/l/l1i-32b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gysr-mb2g"/><path class="cnwa92bez"/><path class="l1i-32b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chassis-ground-48-bold" /></template>
