<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfajlf5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grfajlf5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balls-outline" /></template>
