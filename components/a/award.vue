<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa9s_vb_p.css';
import '../../css/m/mh82_cb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer sa9s_vb_p"/><path class="duoicon-primary-layer mh82_cb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:award" /></template>
