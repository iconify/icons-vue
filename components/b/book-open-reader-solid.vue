<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrplvnbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrplvnbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:book-open-reader-solid" /></template>
