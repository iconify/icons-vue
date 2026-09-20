<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2f7h7_xh.css';
import '../../css/j/jbyel523s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2f7h7_xh"/><path clip-rule="evenodd" class="jbyel523s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:gallery" /></template>
