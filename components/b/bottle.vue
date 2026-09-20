<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-2nubue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-2nubue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle" /></template>
