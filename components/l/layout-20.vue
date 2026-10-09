<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewn1ke3br.css';
import '../../css/n/nthzzhwxx.css';
import '../../css/p/pufh2ab9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="nthzzhwxx"/><path class="pufh2ab9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-20" /></template>
