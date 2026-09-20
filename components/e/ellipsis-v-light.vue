<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7aachdol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7aachdol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-v-light" /></template>
