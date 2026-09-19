<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anrpz00wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anrpz00wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:alarm-add" /></template>
