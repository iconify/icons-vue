<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9s103bcs.css';
import '../../css/n/n3xy1-b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9s103bcs"/><path class="n3xy1-b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:business-workflow-merge-1" /></template>
