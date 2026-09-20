<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_ooxbvp.css';
import '../../css/t/tof83qbtg.css';
import '../../css/k/kgj1lsauv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ty_ooxbvp"/><circle class="tof83qbtg"/><circle class="kgj1lsauv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:ellipsis-v" /></template>
