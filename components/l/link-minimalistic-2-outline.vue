<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbykibczi.css';
import '../../css/f/fm67_nbcb.css';
import '../../css/r/r7elkeb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbykibczi"/><path class="fm67_nbcb"/><path class="r7elkeb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-2-outline" /></template>
