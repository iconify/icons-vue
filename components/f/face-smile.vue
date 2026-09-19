<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g968yccfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g968yccfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-smile" /></template>
