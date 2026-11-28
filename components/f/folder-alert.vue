<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-9m0zvwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-9m0zvwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-alert" /></template>
