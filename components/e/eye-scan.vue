<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_axdubmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_axdubmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:eye-scan" /></template>
