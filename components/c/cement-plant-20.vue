<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzr0hm98u.css';
import '../../css/z/zoam-0bdz.css';
import '../../css/f/fl-um2bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zzr0hm98u"/><path class="zoam-0bdz"/><path class="fl-um2bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cement-plant-20" /></template>
