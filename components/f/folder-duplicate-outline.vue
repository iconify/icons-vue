<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbl2mlbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl2mlbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-duplicate-outline" /></template>
