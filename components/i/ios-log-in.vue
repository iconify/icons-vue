<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_nlublp.css';
import '../../css/b/bpfa_z1vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb_nlublp"/><path class="bpfa_z1vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-log-in" /></template>
