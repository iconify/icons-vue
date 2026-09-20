<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujhqrdbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujhqrdbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:insights-duotone" /></template>
