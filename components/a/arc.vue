<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejz479zpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejz479zpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:arc" /></template>
