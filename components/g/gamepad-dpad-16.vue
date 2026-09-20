<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_k1aixrm.css';
import '../../css/q/qrzlcfwkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k_k1aixrm"/><path clip-rule="evenodd" class="qrzlcfwkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-dpad-16" /></template>
