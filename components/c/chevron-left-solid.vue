<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4n5v94id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4n5v94id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-left-solid" /></template>
