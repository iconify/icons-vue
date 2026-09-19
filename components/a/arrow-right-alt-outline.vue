<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/altw2ob-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="altw2ob-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-right-alt-outline" /></template>
