<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-99oa8q.css';
import '../../css/m/m7s4zt-mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok-99oa8q"/><path class="m7s4zt-mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-json-filled" /></template>
