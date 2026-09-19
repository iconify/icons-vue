<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aae35_ljn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aae35_ljn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-forward-thick-fill" /></template>
