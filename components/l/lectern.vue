<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm38z7b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm38z7b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lectern" /></template>
