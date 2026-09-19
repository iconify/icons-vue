<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km82hcy6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km82hcy6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:caption-outline" /></template>
