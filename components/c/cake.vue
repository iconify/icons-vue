<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8nwnmb-m.css';
import '../../css/p/p9k80_4qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer l8nwnmb-m"/><path class="duoicon-secondary-layer p9k80_4qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:cake" /></template>
