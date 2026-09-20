<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as9l66-0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="as9l66-0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-vert-center-detailed-fill" /></template>
