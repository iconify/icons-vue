<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teszfnbjc.css';
import '../../css/s/sktx1i8jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="teszfnbjc"/><path class="sktx1i8jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bandage-48" /></template>
