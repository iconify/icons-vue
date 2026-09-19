<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bttm99b0u.css';
import '../../css/a/a6m8tsd_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bttm99b0u duoicon-primary-layer"/><path class="a6m8tsd_d duoicon-secondary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:computer-camera-off" /></template>
