<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ai2gp-g.css';
import '../../css/z/zomqz72kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g0ai2gp-g"/><path class="zomqz72kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fmd-light" /></template>
