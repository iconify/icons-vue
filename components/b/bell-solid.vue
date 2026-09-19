<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odcfwjbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odcfwjbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bell-solid" /></template>
