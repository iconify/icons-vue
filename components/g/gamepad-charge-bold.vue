<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udpk4tbla.css';
import '../../css/p/pob1i1ksy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udpk4tbla"/><path clip-rule="evenodd" class="pob1i1ksy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-charge-bold" /></template>
