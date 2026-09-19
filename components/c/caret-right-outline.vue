<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejyw6md3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejyw6md3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-right-outline" /></template>
