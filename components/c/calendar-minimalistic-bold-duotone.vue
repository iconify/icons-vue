<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd465jbnq.css';
import '../../css/n/nxd-6qb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd465jbnq"/><path class="nxd-6qb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-minimalistic-bold-duotone" /></template>
