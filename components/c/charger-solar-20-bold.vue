<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eageplt4r.css';
import '../../css/s/sjlcjjhzm.css';
import '../../css/s/s044fpzgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eageplt4r"/><path class="sjlcjjhzm"/><path class="s044fpzgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-solar-20-bold" /></template>
