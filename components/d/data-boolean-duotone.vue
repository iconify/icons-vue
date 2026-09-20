<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crs9g4qvt.css';
import '../../css/f/fbk-2ebdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crs9g4qvt"/><path clip-rule="evenodd" class="fbk-2ebdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-boolean-duotone" /></template>
