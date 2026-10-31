<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/epokgjbrc.css';
import '../../css/r/rtg5wwmrv.css';
import '../../css/n/nvj7pabfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="epokgjbrc wm-shadow"/><path class="rtg5wwmrv wm-shadow"/><path class="nvj7pabfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:fence" /></template>
