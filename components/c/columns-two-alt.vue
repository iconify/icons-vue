<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhjtetu5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhjtetu5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:columns-two-alt" /></template>
