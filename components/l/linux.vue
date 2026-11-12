<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrbag7b_v.css';
import '../../css/a/aox8suj0x.css';
import '../../css/f/fyfohacvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrbag7b_v"/><path class="aox8suj0x"/><path class="fyfohacvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux" /></template>
