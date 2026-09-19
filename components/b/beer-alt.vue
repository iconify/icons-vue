<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udyqhi_1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udyqhi_1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beer-alt" /></template>
