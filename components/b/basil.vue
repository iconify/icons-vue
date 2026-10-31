<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ts_gbgo.css';
import '../../css/e/eve76ufxm.css';
import '../../css/c/crzx6podm.css';
import '../../css/f/fm-1f-6la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r9ts_gbgo"/><path class="eve76ufxm"/><path class="crzx6podm"/><path class="fm-1f-6la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:basil" /></template>
