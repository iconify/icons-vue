<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvyz_x15a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvyz_x15a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h2-solid" /></template>
