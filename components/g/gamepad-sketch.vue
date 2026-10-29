<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jj08d2qml.css';
import '../../css/j/jew-xxopj.css';
import '../../css/v/vimmpcbiq.css';
import '../../css/u/uiy43vn5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jj08d2qml"/><path class="jew-xxopj wm-a"/><path class="vimmpcbiq wm-k"/><path class="uiy43vn5w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gamepad-sketch" /></template>
