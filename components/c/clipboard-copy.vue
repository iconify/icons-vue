<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlqhq9n4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlqhq9n4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:clipboard-copy" /></template>
