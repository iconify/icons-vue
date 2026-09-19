<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6yrczefu.css';
import '../../css/r/r-t_bpbcz.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6yrczefu"/><path clip-rule="evenodd" class="r-t_bpbcz"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-illustrator-outline" /></template>
