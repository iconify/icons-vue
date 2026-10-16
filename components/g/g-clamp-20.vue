<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tydjinbpb.css';
import '../../css/h/hhk5ccb2m.css';
import '../../css/v/v9vk_uvpw.css';
import '../../css/k/ks180r2vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tydjinbpb"/><path class="hhk5ccb2m"/><path class="v9vk_uvpw"/><path class="ks180r2vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:g-clamp-20" /></template>
