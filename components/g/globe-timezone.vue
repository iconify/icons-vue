<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oax_uo-bh.css';
import '../../css/q/q-6bjtb-l.css';
import '../../css/g/g8itcgf_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oax_uo-bh"/><path class="q-6bjtb-l"/><path class="g8itcgf_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe-timezone" /></template>
