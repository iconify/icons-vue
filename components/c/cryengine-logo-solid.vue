<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc0llq_tf.css';
import '../../css/l/l12z44bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0llq_tf"/><path clip-rule="evenodd" class="l12z44bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cryengine-logo-solid" /></template>
