<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtyp_jihh.css';
import '../../css/f/fh3kbwobr.css';
import '../../css/q/q7cll_b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtyp_jihh"/><path class="fh3kbwobr"/><path clip-rule="evenodd" class="q7cll_b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-date-duotone" /></template>
