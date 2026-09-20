<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpralsssx.css';
import '../../css/g/gaw19yb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpralsssx"/><path class="gaw19yb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:camera" /></template>
