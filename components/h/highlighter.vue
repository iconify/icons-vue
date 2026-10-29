<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r141g95mt.css';
import '../../css/w/wl6kj8h9x.css';
import '../../css/r/r2f7wf--x.css';
import '../../css/c/c4b1g3bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r141g95mt wm-a"/><path class="wl6kj8h9x wm-k"/><path class="r2f7wf--x wm-k"/><path class="c4b1g3bsn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:highlighter" /></template>
