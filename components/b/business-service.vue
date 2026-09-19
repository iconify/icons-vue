<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4grs4bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4grs4bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:business-service" /></template>
