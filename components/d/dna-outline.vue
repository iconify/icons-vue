<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg-6zcbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg-6zcbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dna-outline" /></template>
