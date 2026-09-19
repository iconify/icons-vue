<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/a/an0_1xo_x.css';
import '../../css/o/o1d5h2b_p.css';
import '../../css/d/d10519b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><circle class="an0_1xo_x"/><circle class="o1d5h2b_p"/><path class="d10519b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-happy-alt" /></template>
