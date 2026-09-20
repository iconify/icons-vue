<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge7fm3s-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge7fm3s-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-more-circle-fill" /></template>
