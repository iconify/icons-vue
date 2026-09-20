<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrc_o7bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrc_o7bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:heart-alt-line" /></template>
