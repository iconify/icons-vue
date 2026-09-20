<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2odmxwvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2odmxwvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-2-fill" /></template>
