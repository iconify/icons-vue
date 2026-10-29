<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owokicyeq.css';
import '../../css/b/bkc1rfxdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owokicyeq wm-k"/><path class="bkc1rfxdc wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:code" /></template>
