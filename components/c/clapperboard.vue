<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzvy9qljv.css';
import '../../css/r/r44pubbco.css';
import '../../css/u/uodmxybrc.css';
import '../../css/b/bmxa9_qne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvy9qljv wm-k"/><path class="r44pubbco wm-k"/><path class="uodmxybrc wm-a"/><path class="bmxa9_qne wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:clapperboard" /></template>
