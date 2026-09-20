<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guvw5obdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="guvw5obdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-square-outline" /></template>
