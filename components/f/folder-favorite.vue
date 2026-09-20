<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb973cc3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb973cc3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-favorite" /></template>
