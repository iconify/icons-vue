<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1lsw24hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1lsw24hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:credit-card-plus-alt-outline" /></template>
