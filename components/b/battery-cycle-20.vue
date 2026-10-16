<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-einb7l.css';
import '../../css/w/w73ky16tg.css';
import '../../css/m/m851t0cxs.css';
import '../../css/x/x6bsj-bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ub-einb7l"/><path class="w73ky16tg"/><path class="m851t0cxs"/><path class="x6bsj-bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cycle-20" /></template>
