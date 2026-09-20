<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghylczb-n.css';
import '../../css/s/svi8x9byo.css';
import '../../css/d/dj90s9bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghylczb-n"/><path class="svi8x9byo"/><path clip-rule="evenodd" class="dj90s9bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-forbid-fill" /></template>
