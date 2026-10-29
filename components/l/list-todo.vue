<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/w/wvq8chrbx.css';
import '../../css/d/df8z9fbun.css';
import '../../css/w/wg32sp1ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="wm-k wvq8chrbx"/><path class="df8z9fbun wm-a"/><path class="wg32sp1ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list-todo" /></template>
