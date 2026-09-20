<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2k757bsm.css';
import '../../css/p/p3xr9ebyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2k757bsm"/><path clip-rule="evenodd" class="p3xr9ebyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:drumkit-24" /></template>
