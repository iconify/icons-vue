<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t283ehz.css';
import '../../css/l/l975lbcph.css';
import '../../css/m/m86cqj3me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p2t283ehz"/><path class="l975lbcph"/><path class="m86cqj3me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-bold-duotone" /></template>
