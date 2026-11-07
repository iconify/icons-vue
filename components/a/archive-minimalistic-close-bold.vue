<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipd9i5bbn.css';
import '../../css/n/n3pz-6bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipd9i5bbn"/><path class="n3pz-6bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-minimalistic-close-bold" /></template>
