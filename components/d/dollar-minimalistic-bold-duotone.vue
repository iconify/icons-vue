<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvqe86bhm.css';
import '../../css/p/ps3_ptnuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvqe86bhm"/><path class="ps3_ptnuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dollar-minimalistic-bold-duotone" /></template>
