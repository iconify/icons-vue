<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g90c98oen.css';
import '../../css/t/tk5zlblso.css';
import '../../css/v/vpcsadb2x.css';
import '../../css/m/m1hlppt_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g90c98oen"/><circle class="tk5zlblso"/><circle class="vpcsadb2x"/><path class="m1hlppt_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:integrated-webcam" /></template>
