<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5nkwoc8d.css';
import '../../css/i/i-1cn8fad.css';
import '../../css/p/ptk9v2bpu.css';
import '../../css/j/j9jczgbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k x5nkwoc8d"/><path class="i-1cn8fad wm-k"/><path class="ptk9v2bpu wm-a"/><path class="j9jczgbif wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:gamepad" /></template>
