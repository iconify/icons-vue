<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhqf8nbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":512};
const content = `<path class="rhqf8nbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:junos" /></template>
