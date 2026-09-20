<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lju9ghrlq.css';
import '../../css/c/cbrxaibgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lju9ghrlq"/><path class="cbrxaibgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-restore-filled" /></template>
