<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg8qhc6do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg8qhc6do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cyberdefenders" /></template>
