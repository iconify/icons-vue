<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx0y__vby.css';
import '../../css/m/mpdhyabli.css';
import '../../css/o/o5sq00_9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lx0y__vby"/><path class="mpdhyabli"/><path class="o5sq00_9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eigenfocus" /></template>
