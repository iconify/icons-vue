<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5h0cfbmd.css';
import '../../css/n/n3pz-6bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f5h0cfbmd"/><path class="n3pz-6bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-minimalistic-bold" /></template>
