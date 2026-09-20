<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yarre3bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yarre3bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-agender" /></template>
