<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgv6vubxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgv6vubxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-sharp" /></template>
