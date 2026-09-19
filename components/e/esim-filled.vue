<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js7ccfdti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js7ccfdti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:esim-filled" /></template>
