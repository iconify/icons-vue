<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l96-r8sfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l96-r8sfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-2-outline" /></template>
