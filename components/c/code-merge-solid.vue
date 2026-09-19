<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-ikz9bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-ikz9bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:code-merge-solid" /></template>
