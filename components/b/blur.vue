<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka-seacgp.css';
import '../../css/c/c-9rkjgot.css';
import '../../css/i/i__a0oooy.css';
import '../../css/z/z_jsjpbaa.css';
import '../../css/n/n7pd2ab8h.css';
import '../../css/u/ugo0tuwgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka-seacgp"/><circle class="c-9rkjgot"/><path class="i__a0oooy"/><circle class="z_jsjpbaa"/><path class="n7pd2ab8h"/><circle class="ugo0tuwgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:blur" /></template>
