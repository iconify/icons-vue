<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3zkowdqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3zkowdqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-arrow-up-sharp" /></template>
