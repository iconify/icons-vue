<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv9bp2bij.css';
import '../../css/g/g-trd5b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv9bp2bij"/><path class="g-trd5b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:knob-fill" /></template>
