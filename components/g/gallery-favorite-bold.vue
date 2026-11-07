<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwvsfxegk.css';
import '../../css/o/oswy_sbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwvsfxegk"/><path class="oswy_sbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-favorite-bold" /></template>
