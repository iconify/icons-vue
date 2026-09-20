<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9w5rnv8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9w5rnv8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:clubforce" /></template>
