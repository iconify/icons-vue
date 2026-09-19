<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8qo6njks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8qo6njks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-button-filled" /></template>
