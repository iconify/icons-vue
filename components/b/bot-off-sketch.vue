<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gz9pi8bqa.css';
import '../../css/e/e3o0ig38m.css';
import '../../css/e/ev0fqeb1j.css';
import '../../css/z/zw944ab4t.css';
import '../../css/g/g41fysqtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gz9pi8bqa wm-k"/><path class="e3o0ig38m wm-k"/><path class="ev0fqeb1j wm-a"/><path class="wm-a zw944ab4t"/><path class="g41fysqtd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bot-off-sketch" /></template>
