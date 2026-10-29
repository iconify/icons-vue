<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0rtidb-e.css';
import '../../css/f/fh1vxnxeg.css';
import '../../css/s/s1s0bim7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z0rtidb-e"/><path class="fh1vxnxeg wm-k"/><path class="s1s0bim7b wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cursor" /></template>
