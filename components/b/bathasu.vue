<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo2675bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo2675bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bathasu" /></template>
