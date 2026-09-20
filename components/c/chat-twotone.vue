<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/p/ppfqyn.css';
import '../../css/d/dxl7-q.css';
import '../../css/y/y4wbml.css';
import '../../css/r/ruuz6o.css';
import '../../css/k/kivm5z.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-70.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew ppfqyn"/><path class="dxl7-q iw1iew y4wbml"/><path class="iw1iew ruuz6o y4wbml"/><path class="iw1iew kivm5z y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chat-twotone" /></template>
