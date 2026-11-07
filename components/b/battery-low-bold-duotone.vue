<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eooclpefv.css';
import '../../css/l/l_ge0bc2p.css';
import '../../css/b/bym404azn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eooclpefv"/><path class="l_ge0bc2p"/><path class="bym404azn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-bold-duotone" /></template>
