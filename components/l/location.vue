<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy6pzub9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy6pzub9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:location" /></template>
