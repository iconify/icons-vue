<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznh8nfow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tznh8nfow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:done" /></template>
