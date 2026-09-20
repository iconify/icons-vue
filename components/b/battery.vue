<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acvs9ezds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acvs9ezds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery" /></template>
