<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d39937bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d39937bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-bottom-simple-fill" /></template>
