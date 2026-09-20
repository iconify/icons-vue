<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n638o0bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n638o0bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:argo" /></template>
