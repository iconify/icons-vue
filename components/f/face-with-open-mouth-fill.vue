<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjbf6hs1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjbf6hs1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:face-with-open-mouth-fill" /></template>
