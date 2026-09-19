<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mou0wjb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mou0wjb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bladder-outline-24px" /></template>
