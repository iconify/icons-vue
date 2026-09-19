<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmmzv14io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmmzv14io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-cancel-filled" /></template>
