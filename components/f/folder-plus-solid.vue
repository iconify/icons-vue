<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea76pdpsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea76pdpsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-plus-solid" /></template>
