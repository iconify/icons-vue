<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pep7mub8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pep7mub8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-fill" /></template>
