<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms5-ntotx.css';
import '../../css/s/s3l-i3nyz.css';
import '../../css/e/evbbf8bxp.css';
import '../../css/w/wplu9ikca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5-ntotx wm-k"/><path class="s3l-i3nyz wm-a"/><path class="evbbf8bxp wm-a"/><path class="wm-a wplu9ikca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:loader" /></template>
