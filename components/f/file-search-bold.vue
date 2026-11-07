<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oio3n0tpv.css';
import '../../css/n/nka8deypl.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oio3n0tpv"/><path clip-rule="evenodd" class="nka8deypl"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-search-bold" /></template>
