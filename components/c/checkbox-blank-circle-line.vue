<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aairjvb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aairjvb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-blank-circle-line" /></template>
