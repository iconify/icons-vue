<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thlw7vb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thlw7vb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-wide-narrow-sharp" /></template>
