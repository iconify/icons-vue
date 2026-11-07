<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcjk-wbhz.css';
import '../../css/i/i3vvs1wnr.css';
import '../../css/f/fqll1i-6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjk-wbhz"/><path class="i3vvs1wnr"/><path clip-rule="evenodd" class="fqll1i-6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-bug-bold-duotone" /></template>
