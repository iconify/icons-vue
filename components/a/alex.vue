<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya5ldybze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":264,"height":512};
const content = `<path class="ya5ldybze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:alex" /></template>
