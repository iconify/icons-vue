<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x839ghbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x839ghbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-stop-fill" /></template>
