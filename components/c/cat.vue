<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr58843mv.css';
import '../../css/c/c9r1x5bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr58843mv"/><path class="c9r1x5bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cat" /></template>
