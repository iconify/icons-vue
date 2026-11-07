<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4-2__b2p.css';
import '../../css/z/zdonwh5nc.css';
import '../../css/i/iy-pf8byq.css';
import '../../css/v/vxq9cv80q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4-2__b2p"/><path class="zdonwh5nc"/><path class="iy-pf8byq"/><path class="vxq9cv80q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-bold-duotone" /></template>
