<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc4yfhbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc4yfhbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hop" /></template>
