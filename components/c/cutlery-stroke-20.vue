<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0cnxybhb.css';
import '../../css/q/qeky-4bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k0cnxybhb"/><path class="qeky-4bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cutlery-stroke-20" /></template>
