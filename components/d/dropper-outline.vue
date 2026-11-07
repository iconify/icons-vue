<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d27t_bb-z.css';
import '../../css/t/tucskcrzp.css';
import '../../css/b/b6_4kwocn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d27t_bb-z"/><path class="tucskcrzp"/><path clip-rule="evenodd" class="b6_4kwocn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-outline" /></template>
