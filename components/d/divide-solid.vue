<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi0-5b3gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi0-5b3gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:divide-solid" /></template>
