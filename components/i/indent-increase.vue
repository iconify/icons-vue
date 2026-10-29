<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw83z9b-r.css';
import '../../css/t/t9-82h_yw.css';
import '../../css/d/d0870abvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k zw83z9b-r"/><path class="t9-82h_yw wm-k"/><path class="d0870abvw wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:indent-increase" /></template>
