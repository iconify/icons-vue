<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-f7zs-ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v-f7zs-ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:incorrect-password-remix" /></template>
