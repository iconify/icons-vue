<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe3qplk3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3qplk3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-duotone" /></template>
