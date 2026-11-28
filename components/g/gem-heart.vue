<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dab_wmkpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dab_wmkpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gem-heart" /></template>
