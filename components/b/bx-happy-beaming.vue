<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_qsybka.css';
import '../../css/w/wqbkv8u2i.css';
import '../../css/k/k66cgcc-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_qsybka"/><path class="wqbkv8u2i"/><path class="k66cgcc-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-happy-beaming" /></template>
