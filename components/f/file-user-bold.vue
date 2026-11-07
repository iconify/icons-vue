<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2b6k5bqi.css';
import '../../css/j/j5v3k4mhw.css';
import '../../css/s/se-wl_b4d.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b6k5bqi"/><path class="j5v3k4mhw"/><path clip-rule="evenodd" class="se-wl_b4d"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-user-bold" /></template>
