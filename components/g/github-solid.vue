<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wex9syf4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wex9syf4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:github-solid" /></template>
