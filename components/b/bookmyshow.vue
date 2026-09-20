<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp6iuvngt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp6iuvngt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bookmyshow" /></template>
