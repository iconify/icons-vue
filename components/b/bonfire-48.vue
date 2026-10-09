<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm29_vbfv.css';
import '../../css/q/q534ik57i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pm29_vbfv"/><path class="q534ik57i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bonfire-48" /></template>
