<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz-t8pb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-t8pb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-bold-outline" /></template>
