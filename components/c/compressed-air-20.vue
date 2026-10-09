<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-300obtu.css';
import '../../css/w/we0xbxfdt.css';
import '../../css/s/shaiqxb2f.css';
import '../../css/c/clim4d_fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-300obtu"/><path class="we0xbxfdt"/><path class="shaiqxb2f"/><path class="clim4d_fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressed-air-20" /></template>
