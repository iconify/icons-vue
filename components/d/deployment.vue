<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxz1d9zdu.css';
import '../../css/n/nf61udb6z.css';
import '../../css/t/t-y-wfbey.css';
import '../../css/a/aufd3gbbo.css';
import '../../css/s/sn56facnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gxz1d9zdu"/><path class="nf61udb6z"/><path class="t-y-wfbey"/><path class="aufd3gbbo"/><path class="sn56facnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:deployment" /></template>
