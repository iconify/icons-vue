<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abwkqfblz.css';
import '../../css/j/j7p02hblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="abwkqfblz"/><path class="j7p02hblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hair-dryer-20" /></template>
