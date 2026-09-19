<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jif2-ff-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jif2-ff-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:book-open-solid" /></template>
