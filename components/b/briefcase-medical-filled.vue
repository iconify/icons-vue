<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed-8irbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ed-8irbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:briefcase-medical-filled" /></template>
