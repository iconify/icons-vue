<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkb1im0po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkb1im0po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:facebook-solid" /></template>
