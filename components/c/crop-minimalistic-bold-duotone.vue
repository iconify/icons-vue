<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenyhg4uf.css';
import '../../css/w/wljgqrbai.css';
import '../../css/s/suoyyrb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zenyhg4uf"/><path class="wljgqrbai"/><path class="suoyyrb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-minimalistic-bold-duotone" /></template>
