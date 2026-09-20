<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhl0h1bhb.css';
import '../../css/j/jcs27cipf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhl0h1bhb"/><path class="jcs27cipf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hand-taking-leaf-1" /></template>
