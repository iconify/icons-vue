<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejutc9btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejutc9btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:icecream-outline" /></template>
