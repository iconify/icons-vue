<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udeabbl7f.css';
import '../../css/b/b82thot2p.css';
import '../../css/f/fkr7gxrju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="udeabbl7f"/><path class="b82thot2p"/><path class="fkr7gxrju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-pipeline-20-bold" /></template>
