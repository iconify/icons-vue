<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mp0wbzm.css';
import '../../css/w/wkylhn4dt.css';
import '../../css/p/pvx_7s2bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="wkylhn4dt"/><path class="pvx_7s2bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fireplace-48" /></template>
