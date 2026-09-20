<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0wd5e82z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0wd5e82z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-type-sharp" /></template>
