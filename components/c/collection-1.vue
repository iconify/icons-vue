<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwk220rgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwk220rgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:collection-1" /></template>
