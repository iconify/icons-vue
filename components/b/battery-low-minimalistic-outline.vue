<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzibxeopw.css';
import '../../css/o/osemxebgc.css';
import '../../css/o/ocb7_jb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzibxeopw"/><path clip-rule="evenodd" class="osemxebgc"/><path class="ocb7_jb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-minimalistic-outline" /></template>
