<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbmt5i9bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbmt5i9bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:homeadvisor" /></template>
