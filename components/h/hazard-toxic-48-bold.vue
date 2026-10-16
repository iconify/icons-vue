<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mjsubix.css';
import '../../css/y/yut4brtiz.css';
import '../../css/i/iswbwirhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="yut4brtiz"/><path class="iswbwirhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-toxic-48-bold" /></template>
