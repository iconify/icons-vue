<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ai2gp-g.css';
import '../../css/p/phudelb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g0ai2gp-g"/><path class="phudelb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fmd-light" /></template>
