<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8y7oacxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8y7oacxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bell-add" /></template>
