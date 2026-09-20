<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd45x_ltj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd45x_ltj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-alt-1-fill" /></template>
