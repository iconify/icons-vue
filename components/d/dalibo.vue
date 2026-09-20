<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqho8nb-e.css';
import '../../css/k/k7wugp4nh.css';
import '../../css/h/hnviy2tvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqho8nb-e"/><path class="k7wugp4nh"/><path class="hnviy2tvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dalibo" /></template>
