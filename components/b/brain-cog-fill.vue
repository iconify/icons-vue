<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ur12suv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9ur12suv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain-cog-fill" /></template>
