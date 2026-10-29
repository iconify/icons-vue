<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dckrksbvf.css';
import '../../css/d/dn9oi3j2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dckrksbvf wm-k"/><path class="dn9oi3j2f wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:heading" /></template>
