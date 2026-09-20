<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daefol3mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daefol3mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-top-right" /></template>
