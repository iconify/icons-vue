<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r95j0mbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r95j0mbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-text-left" /></template>
