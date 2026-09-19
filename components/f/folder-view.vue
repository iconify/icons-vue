<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dzrxlf1os.css';
import '../../css/g/gwncqhcpc.css';
import '../../css/u/ufugkktpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dzrxlf1os"/><path class="gwncqhcpc"/><path class="ufugkktpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-view" /></template>
