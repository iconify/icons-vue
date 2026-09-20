<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9phxfb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9phxfb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:credit-card-detailed-alt-fill" /></template>
