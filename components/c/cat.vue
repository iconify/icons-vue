<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1sqy38ml.css';
import '../../css/u/u1u-os4ws.css';
import '../../css/b/b0fe4tbca.css';
import '../../css/f/fkadcub_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1sqy38ml"/><path class="u1u-os4ws"/><path class="b0fe4tbca"/><path class="fkadcub_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cat" /></template>
