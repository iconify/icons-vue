<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp7nxbb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp7nxbb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-right-solid" /></template>
