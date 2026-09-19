<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyl1kfb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uyl1kfb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-command-small" /></template>
