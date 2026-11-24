<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-5sdbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo-5sdbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flag-triangle-right-filled" /></template>
