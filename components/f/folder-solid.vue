<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxz2te--u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxz2te--u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-solid" /></template>
