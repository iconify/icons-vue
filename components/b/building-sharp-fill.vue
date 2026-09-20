<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwf82ffby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jwf82ffby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-sharp-fill" /></template>
