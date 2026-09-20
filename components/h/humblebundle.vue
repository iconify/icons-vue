<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8rw6-4fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8rw6-4fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:humblebundle" /></template>
