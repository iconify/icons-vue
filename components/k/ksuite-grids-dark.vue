<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajrs5fbzp.css';
import '../../css/h/hkgap18lv.css';
import '../../css/t/t_aewkbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajrs5fbzp"/><path class="hkgap18lv"/><path class="t_aewkbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-grids-dark" /></template>
