<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9j6jnqno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9j6jnqno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:clouds-filled" /></template>
