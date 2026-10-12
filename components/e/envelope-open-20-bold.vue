<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/silr-gb_u.css';
import '../../css/t/tdqcdzb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="silr-gb_u"/><path class="tdqcdzb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:envelope-open-20-bold" /></template>
