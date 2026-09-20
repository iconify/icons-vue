<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdnb4ibza.css';
import '../../css/v/va7yy6tym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fdnb4ibza"/><path class="va7yy6tym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-button-bottom-16" /></template>
