<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/petscgbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="petscgbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:invision-logo-block" /></template>
