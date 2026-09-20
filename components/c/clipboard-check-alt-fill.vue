<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp3m9gbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fp3m9gbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-check-alt-fill" /></template>
