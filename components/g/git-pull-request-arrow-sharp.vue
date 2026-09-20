<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3fqfacvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3fqfacvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-pull-request-arrow-sharp" /></template>
