<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka8y21bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka8y21bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-remove-outline" /></template>
