<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey4hq3keo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ey4hq3keo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-male-20-solid" /></template>
