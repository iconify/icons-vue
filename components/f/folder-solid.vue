<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go4fhbbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go4fhbbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-solid" /></template>
