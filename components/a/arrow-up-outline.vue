<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya9gfz95a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya9gfz95a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-outline" /></template>
