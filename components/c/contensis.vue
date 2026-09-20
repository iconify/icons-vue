<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhj7tzbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhj7tzbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:contensis" /></template>
