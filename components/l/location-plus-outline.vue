<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5rdgsbpl.css';
import '../../css/i/ipz_6dbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5rdgsbpl"/><path clip-rule="evenodd" class="ipz_6dbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:location-plus-outline" /></template>
