<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ephwb-o.css';
import '../../css/v/v_devvdob.css';
import '../../css/f/fwasz7buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="v_devvdob"/><path class="fwasz7buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:lebanon" /></template>
