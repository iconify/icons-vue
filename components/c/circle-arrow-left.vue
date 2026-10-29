<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdx-_oc4k.css';
import '../../css/r/rf06sdq9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdx-_oc4k wm-k"/><path class="rf06sdq9n wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-arrow-left" /></template>
