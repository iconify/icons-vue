<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7q6nqbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7q6nqbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-export" /></template>
