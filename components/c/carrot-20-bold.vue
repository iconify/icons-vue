<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l361dvbca.css';
import '../../css/h/hud-elbct.css';
import '../../css/a/ahkc9jbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l361dvbca"/><path class="hud-elbct"/><path class="ahkc9jbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carrot-20-bold" /></template>
