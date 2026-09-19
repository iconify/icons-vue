<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbi1web-l.css';
import '../../css/c/c8qbtokgo.css';
import '../../css/l/l-0qr7dzn.css';
import '../../css/q/qvmzwopuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbi1web-l"/><path class="c8qbtokgo"/><path class="l-0qr7dzn"/><path class="qvmzwopuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:envelopewithlightning" /></template>
