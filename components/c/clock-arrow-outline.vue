<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkci47bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkci47bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clock-arrow-outline" /></template>
