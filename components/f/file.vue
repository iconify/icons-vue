<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2sandlqm.css';
import '../../css/x/xgtqlm-cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer s2sandlqm"/><path class="duoicon-primary-layer xgtqlm-cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:file" /></template>
