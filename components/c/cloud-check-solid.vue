<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdzs51bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gdzs51bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-check-solid" /></template>
