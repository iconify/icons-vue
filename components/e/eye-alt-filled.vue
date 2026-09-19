<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymz-vs81r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymz-vs81r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-alt-filled" /></template>
