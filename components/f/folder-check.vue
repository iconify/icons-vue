<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhxqnhb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhxqnhb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-check" /></template>
