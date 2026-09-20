<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crn5zwh2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="crn5zwh2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-password-bold" /></template>
