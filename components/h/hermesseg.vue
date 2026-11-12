<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg1-4zbux.css';
import '../../css/y/yg-vkub-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="lg1-4zbux"/><path class="yg-vkub-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermesseg" /></template>
