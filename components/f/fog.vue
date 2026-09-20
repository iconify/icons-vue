<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bghqw598p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bghqw598p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fog" /></template>
