<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua1c_6t9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1c_6t9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-bookmark" /></template>
