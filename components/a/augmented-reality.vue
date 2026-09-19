<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7m4j-afs.css';
import '../../css/g/g4h-wyhlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7m4j-afs"/><path class="g4h-wyhlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:augmented-reality" /></template>
