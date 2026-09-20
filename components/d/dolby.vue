<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vet4z41ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vet4z41ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dolby" /></template>
