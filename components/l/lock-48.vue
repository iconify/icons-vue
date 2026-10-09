<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6deh2baw.css';
import '../../css/l/lc3h535iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6deh2baw"/><path class="lc3h535iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-48" /></template>
