<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh78-0bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh78-0bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:insert-row-before-outline" /></template>
