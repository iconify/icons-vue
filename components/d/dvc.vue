<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejpz-g1jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejpz-g1jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dvc" /></template>
