<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhe7xubvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uhe7xubvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:archive-alt-fill" /></template>
