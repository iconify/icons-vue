<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcti67wgz.css';
import '../../css/v/votvkdbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcti67wgz"/><path class="votvkdbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-switch-duotone" /></template>
