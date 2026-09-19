<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em-ossnxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em-ossnxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:feather" /></template>
