<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h991oabes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h991oabes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:component-boolean" /></template>
