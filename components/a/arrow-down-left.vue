<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz0t0xciq.css';
import '../../css/u/umqjyb9su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz0t0xciq wm-k"/><path class="umqjyb9su wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-down-left" /></template>
