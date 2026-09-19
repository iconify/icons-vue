<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5i95fbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5i95fbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-up-solid" /></template>
