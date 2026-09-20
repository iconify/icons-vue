<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9ew3n9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy9ew3n9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-sharp" /></template>
