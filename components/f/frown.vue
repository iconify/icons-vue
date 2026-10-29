<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utqzt6bcp.css';
import '../../css/q/qt8u0z4vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="qt8u0z4vf wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:frown" /></template>
