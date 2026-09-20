<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s07kv3b7t.css';
import '../../css/a/afv_f682n.css';
import '../../css/f/f4tfatmwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="s07kv3b7t"/><path class="afv_f682n"/><circle class="f4tfatmwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:camera-duotone-line" /></template>
