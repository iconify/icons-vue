<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uflyx8uae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uflyx8uae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-search-sharp" /></template>
