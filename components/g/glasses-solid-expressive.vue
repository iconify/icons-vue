<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbmlh9n1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbmlh9n1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:glasses-solid-expressive" /></template>
