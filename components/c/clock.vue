<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyneov3ti.css';
import '../../css/j/jiglepbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer iyneov3ti"/><path class="duoicon-primary-layer jiglepbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:clock" /></template>
