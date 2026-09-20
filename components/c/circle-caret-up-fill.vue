<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0pyhdc2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0pyhdc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-up-fill" /></template>
