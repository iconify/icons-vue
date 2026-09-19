<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzt08gbvp.css';
import '../../css/i/i2pz7cbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzt08gbvp"/><path class="i2pz7cbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:compass-alt" /></template>
