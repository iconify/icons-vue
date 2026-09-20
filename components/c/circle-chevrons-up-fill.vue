<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx70z0b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx70z0b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-up-fill" /></template>
