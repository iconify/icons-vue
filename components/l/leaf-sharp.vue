<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9sjfqkke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9sjfqkke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:leaf-sharp" /></template>
