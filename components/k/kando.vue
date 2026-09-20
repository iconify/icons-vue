<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w970jmblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w970jmblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:kando" /></template>
