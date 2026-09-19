<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn39dyf6b.css';
import '../../css/j/jpc-28bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn39dyf6b"/><path class="jpc-28bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-zip-filled" /></template>
