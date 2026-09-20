<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcm739wxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcm739wxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:earthquake-global-seismic-wave-bold" /></template>
