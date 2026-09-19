<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy4_knhwd.css';
import '../../css/z/zsplw2euu.css';
import '../../css/x/xxfidpltx.css';
import '../../css/f/fjdufdgrf.css';
import '../../css/l/lair98k-j.css';
import '../../css/b/bb6dw3b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iy4_knhwd"/><path class="zsplw2euu"/><circle class="xxfidpltx"/><circle class="fjdufdgrf"/><path class="lair98k-j"/><circle class="bb6dw3b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cooking" /></template>
