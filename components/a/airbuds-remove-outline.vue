<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu0k8wbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu0k8wbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-remove-outline" /></template>
