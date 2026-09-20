<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu7-0-q3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu7-0-q3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:apachecassandra" /></template>
