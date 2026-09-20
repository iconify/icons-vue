<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayjtokb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayjtokb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-text-delete-outline" /></template>
