<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffhewbcz.css';
import '../../css/b/bcag0_byz.css';
import '../../css/m/m3mc73wcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pffhewbcz"/><path class="bcag0_byz"/><path class="m3mc73wcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:chart-pie" /></template>
