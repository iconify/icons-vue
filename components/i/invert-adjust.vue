<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovpu7tbvu.css';
import '../../css/i/iahtnrboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovpu7tbvu"/><path class="iahtnrboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:invert-adjust" /></template>
