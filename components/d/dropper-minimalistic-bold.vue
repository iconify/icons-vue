<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1hxn4bwg.css';
import '../../css/u/ud-yki_gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1hxn4bwg"/><path class="ud-yki_gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-bold" /></template>
