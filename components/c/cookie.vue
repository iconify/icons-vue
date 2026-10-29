<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imnma-bab.css';
import '../../css/f/fju53jboa.css';
import '../../css/c/ck4f-q3mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imnma-bab wm-k"/><path class="fju53jboa wm-a"/><path class="ck4f-q3mq wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cookie" /></template>
