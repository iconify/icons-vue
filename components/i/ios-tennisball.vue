<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pufuoacsr.css';
import '../../css/o/o1h606vtq.css';
import '../../css/t/ts-4c6cxu.css';
import '../../css/b/bo0gn7djo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pufuoacsr"/><path class="o1h606vtq"/><path class="ts-4c6cxu"/><path class="bo0gn7djo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-tennisball" /></template>
