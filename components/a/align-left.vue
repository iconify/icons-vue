<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0_24jbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0_24jbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-left" /></template>
