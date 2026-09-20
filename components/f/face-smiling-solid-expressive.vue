<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxct1bw3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxct1bw3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:face-smiling-solid-expressive" /></template>
