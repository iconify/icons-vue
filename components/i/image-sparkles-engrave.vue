<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tek2khblr.css';
import '../../css/y/y2xhkpblq.css';
import '../../css/y/yia3ybcxs.css';
import '../../css/q/qxvwfm8fu.css';
import '../../css/a/ain1tnbxt.css';
import '../../css/s/sy7kpcbuo.css';
import '../../css/q/qdzstlt9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tek2khblr wm-k"/><path class="wm-a y2xhkpblq"/><path class="wm-s yia3ybcxs"/><path class="qxvwfm8fu wm-shadow"/><path class="ain1tnbxt wm-k"/><path class="sy7kpcbuo wm-a"/><path class="qdzstlt9t wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-sparkles-engrave" /></template>
