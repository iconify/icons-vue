<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abw1tpbib.css';
import '../../css/f/fsolhac6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="abw1tpbib"/><path class="fsolhac6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landslide-20" /></template>
