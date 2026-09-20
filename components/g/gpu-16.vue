<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfu3-dmkg.css';
import '../../css/a/aukw43xsk.css';
import '../../css/q/qy58zchov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xfu3-dmkg"/><path class="aukw43xsk"/><path clip-rule="evenodd" class="qy58zchov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gpu-16" /></template>
