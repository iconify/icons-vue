<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aikme3bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aikme3bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-rounded-error" /></template>
