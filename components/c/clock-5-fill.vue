<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7csbubqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7csbubqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-5-fill" /></template>
