<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwc28duwl.css';
import '../../css/p/p0vvxskvk.css';
import '../../css/r/r51vm3woy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwc28duwl wm-k"/><path class="p0vvxskvk wm-k"/><path class="r51vm3woy wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevron-first" /></template>
