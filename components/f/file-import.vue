<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu1-mmbtf.css';
import '../../css/n/n3w3yo25d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu1-mmbtf"/><path class="n3w3yo25d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:file-import" /></template>
