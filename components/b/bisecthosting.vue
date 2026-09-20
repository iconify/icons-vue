<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz35gbsha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz35gbsha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bisecthosting" /></template>
