<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv_p3kcsw.css';
import '../../css/w/w6x-4ipkl.css';
import '../../css/x/x8_a0bb_i.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv_p3kcsw"/><path class="w6x-4ipkl"/><path clip-rule="evenodd" class="x8_a0bb_i"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-audio-bold" /></template>
