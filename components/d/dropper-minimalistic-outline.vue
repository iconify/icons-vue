<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-8g_b_v.css';
import '../../css/r/r-w9wkbha.css';
import '../../css/o/of2duy_cb.css';
import '../../css/h/h3-vuzbus.css';
import '../../css/j/jrec5m78l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-8g_b_v"/><path class="r-w9wkbha"/><path class="of2duy_cb"/><path clip-rule="evenodd" class="h3-vuzbus"/><path clip-rule="evenodd" class="jrec5m78l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-outline" /></template>
