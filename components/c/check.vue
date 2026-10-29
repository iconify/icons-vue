<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-kspbgm.css';
import '../../css/f/f-y-gabit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id-kspbgm"/><path class="f-y-gabit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:check" /></template>
