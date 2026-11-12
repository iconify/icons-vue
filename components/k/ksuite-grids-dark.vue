<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrb10v-km.css';
import '../../css/y/yhs-rpbzu.css';
import '../../css/t/t_aewkbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrb10v-km"/><path class="yhs-rpbzu"/><path class="t_aewkbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-grids-dark" /></template>
