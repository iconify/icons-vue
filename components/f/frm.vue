<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgxln0b_c.css';
import '../../css/h/hlm14cb_n.css';
import '../../css/h/h-clu1byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgxln0b_c"/><path class="hlm14cb_n"/><path class="h-clu1byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:frm" /></template>
