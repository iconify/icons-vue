<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f4lfqelzl.css';
import '../../css/v/vncdglbxf.css';
import '../../css/d/dj6hz0ywu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f4lfqelzl"/><path class="vncdglbxf"/><path class="dj6hz0ywu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-key-object" /></template>
