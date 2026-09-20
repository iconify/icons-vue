<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq7wbxbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq7wbxbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:broom" /></template>
