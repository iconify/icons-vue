<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpy7dbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpy7dbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:fork" /></template>
