<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj3tasbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj3tasbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-connect" /></template>
