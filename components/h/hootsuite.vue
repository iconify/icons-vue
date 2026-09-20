<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu6vuzh5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu6vuzh5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hootsuite" /></template>
