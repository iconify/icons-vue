<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6pes-bxs.css';
import '../../css/h/hknnmqaty.css';
import '../../css/p/pj25m4b3c.css';
import '../../css/s/sp8nadr0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6pes-bxs wm-k"/><path class="hknnmqaty wm-k"/><path class="pj25m4b3c wm-k"/><path class="sp8nadr0y wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:hard-drive" /></template>
