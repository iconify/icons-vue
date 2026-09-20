<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekztc3dhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekztc3dhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-up-bold" /></template>
