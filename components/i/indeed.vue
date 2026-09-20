<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kan00ac-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kan00ac-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:indeed" /></template>
