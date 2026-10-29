<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwx5nsbif.css';
import '../../css/h/hustz32ji.css';
import '../../css/i/ieqi3o5qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwx5nsbif wm-k"/><path class="hustz32ji wm-a"/><path class="ieqi3o5qf wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:clipboard-check" /></template>
