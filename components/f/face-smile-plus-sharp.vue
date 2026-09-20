<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjekp7b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjekp7b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-plus-sharp" /></template>
