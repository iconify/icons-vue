<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhocsxiwx.css';
import '../../css/h/hlr7qvbgb.css';
import '../../css/y/y1m3u927f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhocsxiwx"/><path class="hlr7qvbgb"/><path class="y1m3u927f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:floor-lamp-minimalistic-bold" /></template>
