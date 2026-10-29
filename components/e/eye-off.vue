<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3gm-abug.css';
import '../../css/g/gxgk1_b8t.css';
import '../../css/m/mbzw4qy1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3gm-abug wm-k"/><path class="gxgk1_b8t wm-s"/><path class="mbzw4qy1w wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:eye-off" /></template>
