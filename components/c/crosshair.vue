<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwznl2b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwznl2b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crosshair" /></template>
