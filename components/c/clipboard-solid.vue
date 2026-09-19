<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoe62lluo.css';
import '../../css/u/uy_7ftb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoe62lluo"/><path class="uy_7ftb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:clipboard-solid" /></template>
