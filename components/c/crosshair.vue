<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivjsphbpy.css';
import '../../css/r/rev37acue.css';
import '../../css/y/yeraqkb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivjsphbpy wm-k"/><path class="rev37acue wm-k"/><path class="wm-a yeraqkb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:crosshair" /></template>
