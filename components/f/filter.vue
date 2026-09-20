<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvd164trn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvd164trn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:filter" /></template>
