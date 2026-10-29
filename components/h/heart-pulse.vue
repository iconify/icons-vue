<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b38sfdbfi.css';
import '../../css/a/a6bur7awm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b38sfdbfi wm-k"/><path class="a6bur7awm wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:heart-pulse" /></template>
