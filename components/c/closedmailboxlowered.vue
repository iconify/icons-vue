<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f91lhmb6q.css';
import '../../css/s/sv5qa1b8r.css';
import '../../css/m/mkpacubsd.css';
import '../../css/l/l5rfbdc0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f91lhmb6q"/><path class="sv5qa1b8r"/><path class="mkpacubsd"/><path class="l5rfbdc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:closedmailboxlowered" /></template>
