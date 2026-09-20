<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0a6y8b1l.css';
import '../../css/u/u407k86qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0a6y8b1l"/><path class="u407k86qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:briefcases-fill" /></template>
