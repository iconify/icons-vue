<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovg9qx-rh.css';
import '../../css/i/iz8c3l5-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovg9qx-rh"/><path class="iz8c3l5-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-search-duotone" /></template>
