<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-9okypbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-9okypbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:google" /></template>
