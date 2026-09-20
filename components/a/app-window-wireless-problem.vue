<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz18_1bea.css';
import '../../css/p/p49d8zb-f.css';
import '../../css/v/v3z8t2bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz18_1bea"/><path class="p49d8zb-f"/><path class="v3z8t2bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:app-window-wireless-problem" /></template>
