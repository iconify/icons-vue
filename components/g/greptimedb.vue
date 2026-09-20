<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zajy16b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zajy16b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:greptimedb" /></template>
